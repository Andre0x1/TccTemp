# Importance-Driven Deep Learning System Testing

S. Gerasimou, H. F. Eniser, A. Sen and A. Cakan, "Importance-Driven Deep Learning System Testing," 2020 IEEE/ACM 42nd International Conference on Software Engineering (ICSE), 2020, pp. 702-713. (https://doi.org/10.1145/3377811.3380391)
doi: [10.1145/3377811.3380391]

## 1. Fichamento de Conteúdo

Os autores do artigo explicam como sistemas baseados em algoritmos _Deep Learning_ (DL) se tornaram essenciais como ferramentas para solução de problemas de engenharia devido a sua capacidade de resolução de problemas complexo, como por exemplo o reconhecimento de padrões e imagens, porém para utilizar esta tecnologia em aplicações de alto risco necessita de um alto grau de segurança e testes. No entanto utilizar as práticas de testes mais comuns e recomendadas não é ideal devido ao grande tamanho de sistema DL existentes no mercado e que cada sistema possui suas próprias forma de realizar o processo de decisão, logo se torna necessário utilizar uma forma de priorizar os processos que precisam ser focados nos testes. Logo foi proposto uma nova ferramenta que para realizar a criação dos testes no sistema, ela se basearia inicialmente na metodologia _Importance-Driven_ (IDC), ou seja seria analisada a importância de cada neurônio e sua relevância (_weights_) em relação aos neurônios adjacentes e a partir destes dados determinar os pontos críticos do sistema. A ferramenta apresentada pelo artigo foi implementada inicialmente como protótipo utilizando como base _frameworks_ de DL _open source_, que com baseados nos dados obtidos foi possível identificar que a nova metodologia apresentado obteve resultados semelhantes e até superiores as ferramentas atuais utilizadas para criação dos testes, os autores ainda pretendem realizaram outros estudos a fim de melhoras a ferramenta proposta e utilizara base de dados mais robustas para refinar ainda mais os resultados.

## 2. Fichamento Bibliográfico

- _Deep Learning_ (Aprendizagem profunda) é um ramo do estudo de machine learning que é baseado em um conjunto de algoritmos que tentam modelar abstrações de alto nível de dados, usando um grafo com várias camadas de processamento, compostas de várias transformações (Pagina 2).

- _Importance-Driven_ (metodologia baseado em importância) metodologia apresentada pelo artigo que determina que o valor de determinado elemento no conjunto é baseado na sua importância no mesmo (Pagina 2).

- Neurônios é um componente que calcula a soma ponderada de vários inputs, aplica uma função e passa o resultado adiante, formando a uma sequencia (Pagina 4).

- _weights_ (peso) é um valor dado a cada neurônio que determina sua influência na rede (Pagina 5).

## 3. Fichamento de Citações

- _"Deep Learning (DL) systems are key enablers for engineering intelligent applications due to their ability to solve complex tasks such as image recognition and machine translation. Nevertheless, using DL systems in safety- and security-critical applications requires to provide testing evidence for their dependable operation."_
- _"However, testing DL systems by simply adopting principles recommended by these standards is not straightforward. The lack of a system specification regulating the inference mechanism to be learnt combined with the data-driven programming paradigm makes impossible to explicitly encode the expected DL system be- haviour into its control flow structures."_
- _"The purpose of importance analysis is to identify neurons within a DL system that are key contributors to decision-making. Given an input, information within a DL system is propagated according to the strength of connections (weights) between neurons in successive layers. As such, the activity of some neurons influences more
  the capabilities of the system to make correct decisions [46]."_
