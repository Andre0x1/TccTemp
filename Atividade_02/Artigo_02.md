# Deep learning based software defect prediction

Qiao, L., Li, X., Umer, Q., & Guo, P. (2020). Deep learning based software defect prediction. Neurocomputing, 385, 100-110. doi: [10.1016/j.neucom.2019.11.067](https://doi.org/10.1016/j.neucom.2019.11.067)

## 1. Fichamento de Conteúdo

Com o aumento da complexidade dos sistemas também aconteceu o aumento da frequência de defeitos em suas funcionalidades, causando impactos negativos na confiabilidade destes sistemas e para evitar que isso aconteça são implementadas diversas medidas para evitar que tais defeitos aconteçam, porém tais medidas podem gastar até mesmo 80% do orçamento do projeto. Com base nesta afirmação foram geradas diversas técnicas e ferramentas para detectar falhas antes de sua implementação fazendo com que as atividades de correção possam ser mais ágeis e focadas nos módulos que tem mais chances de causar defeitos, porém estas técnicas apenas dão uma ideia geral dos locais onde podem acontecer erros e normalmente gastam muito tempo para serem implementadas. Os autores do artigo propõem uma nova ferramenta baseada em _Deep Learning_ com o propósito de detectar possíveis regiões de defeito de forma simples, rápida e eficaz, utilizando métricas de qualidade preestabelecidas. A ferramenta funciona da seguinte maneira: primeiro realizando o treinamento de um modelo de detecção de defeitos e em seguida passando os resultados do treino para um modelo seguinte, o treinamento é realizado obtendo inicialmente dado de repositórios que possuem métricas de qualidade definidas, em seguida o modelo é treinado para identificar tais métricas e procura-las em um outro modelo e a partir dos dados obtidos contar e identificar locais de falha, o treinamento é realizado diversas vezes até obter resultados satisfatórios para a amostra. Após os testes inicias da ferramenta, ela conseguiu gerar uma melhora na diminuição de defeitos após ter sido utilizada, obtendo uma redução de 2% ~ 3% na media de erros gerados, no futuro os autores pretendem analisar os resultados obtidos utilizando repositórios maiores e com diversas linguagens de programação.

## 2. Fichamento Bibliográfico

- _Deep Learning_ (Aprendizagem profunda) é um ramo do estudo de machine learning que é baseado em um conjunto de algoritmos que tentam modelar abstrações de alto nível de dados, usando um grafo com várias camadas de processamento, compostas de várias transformações.

- _Importance-Driven_ (metodologia baseado em importância) metodologia apresentada pelo artigo que determina que o valor de determinado elemento no conjunto é baseado na sua importância no mesmo.

- Neurônios é um componente que calcula a soma ponderada de vários inputs, aplica uma função e passa o resultado adiante, formando a uma sequencia.

- _weights_ (peso) é um valor dado a cada neurônio que determina sua influência na rede.

## 3. Fichamento de Citações

- _"Deep Learning (DL) systems are key enablers for engineering intelligent applications due to their ability to solve complex tasks such as image recognition and machine translation. Nevertheless, using DL systems in safety- and security-critical applications requires to provide testing evidence for their dependable operation."_
- _"However, testing DL systems by simply adopting principles recommended by these standards is not straightforward. The lack of a system specification regulating the inference mechanism to be learnt combined with the data-driven programming paradigm makes impossible to explicitly encode the expected DL system be- haviour into its control flow structures."_
- _"The purpose of importance analysis is to identify neurons within a DL system that are key contributors to decision-making. Given an input, information within a DL system is propagated according to the strength of connections (weights) between neurons in successive layers. As such, the activity of some neurons influences more
  the capabilities of the system to make correct decisions [46]."_
