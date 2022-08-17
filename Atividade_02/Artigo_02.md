# Deep learning based software defect prediction

Qiao, L., Li, X., Umer, Q., & Guo, P. (2020). Deep learning based software defect prediction. Neurocomputing, 385, 100-110. doi: [10.1016/j.neucom.2019.11.067](https://doi.org/10.1016/j.neucom.2019.11.067)

## 1. Fichamento de Conteúdo

Com o aumento da complexidade dos sistemas também aconteceu o aumento da frequência de defeitos em suas funcionalidades, causando impactos negativos na confiabilidade destes sistemas e para evitar que isso aconteça são implementadas diversas medidas para evitar que tais defeitos aconteçam, porém tais medidas podem gastar até mesmo 80% do orçamento do projeto. Com base nesta afirmação foram geradas diversas técnicas e ferramentas para detectar falhas antes de sua implementação fazendo com que as atividades de correção possam ser mais ágeis e focadas nos módulos que tem mais chances de causar defeitos, porém estas técnicas apenas dão uma ideia geral dos locais onde podem acontecer erros e normalmente gastam muito tempo para serem implementadas. Os autores do artigo propõem uma nova ferramenta baseada em _Deep Learning_ com o propósito de detectar possíveis regiões de defeito de forma simples, rápida e eficaz, utilizando métricas de qualidade preestabelecidas. A ferramenta funciona da seguinte maneira: primeiro realizando o treinamento de um modelo de detecção de defeitos e em seguida passando os resultados do treino para um modelo seguinte, o treinamento é realizado obtendo inicialmente dado de repositórios que possuem métricas de qualidade definidas, em seguida o modelo é treinado para identificar tais métricas e procura-las em um outro modelo e a partir dos dados obtidos contar e identificar locais de falha, o treinamento é realizado diversas vezes até obter resultados satisfatórios para a amostra. Após os testes inicias da ferramenta, ela conseguiu gerar uma melhora na diminuição de defeitos após ter sido utilizada, obtendo uma redução de 3% ~ 13% na media de erros gerados, no futuro os autores pretendem analisar os resultados obtidos utilizando repositórios maiores e com diversas linguagens de programação.

## 2. Fichamento Bibliográfico

- _Deep Learning_ (Aprendizagem profunda) é um ramo do estudo de machine learning que é baseado em um conjunto de algoritmos que tentam modelar abstrações de alto nível de dados, usando um grafo com várias camadas de processamento, compostas de várias transformações.

- Treinamento (Aprendizado) etapa de instruções passada ao sistema para que possa ser analisadas e reproduzidas .

- Defeitos é qualquer imperfeição ou inconsistência no produto do software ou em seu processo, um defeito é também uma não conformidade.

## 3. Fichamento de Citações

- _"The complexity of modern software systems is increasing, and the resulting software applications often contain defects that can have severe negative impacts on the reliability and robustness of these applications."_
- _"Such defects might lead to failures or produce unexpected results. To reduce failures and improve software quality, many software quality assurance activities (e.g., defect prediction, code re- view and unit testing) are employed. Such activities typically cost approximately 80% of the total budget of a project"_
- _"In contrast, predicting the number of defects provides a spe- cific estimate of the defects in a given module. Thus, the practitioners of software quality assurance activities can pay more attention to modules that have more defects and allocate their lim- ited test resources more efficiently and optimally."_
- _"An overview of the deep learning-based software defect predic- tion is depicted in Fig. 1 , which shows that the proposed approach is composed of two steps: training a deep learning-based defect prediction model (i.e., DPNN model ) and performing defect predic- tion for new modules based on the trained model."_
- _"Compared with these state-of-art approaches on two well-known datasets, the proposed approach achieves a significant reduction in the mean square error (varying between 3% and 13%) and improves the squared correlation coefficient (varying between 2% and 27%)"_
