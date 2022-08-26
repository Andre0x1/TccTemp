# Poster: Performance Testing Driven by Reinforcement Learning

M. H. Moghadam, M. Saadatmand, M. Borg, M. Bohlin and B. Lisper, "Poster: Performance Testing Driven by Reinforcement Learning," 2020 IEEE 13th International Conference on Software Testing, Validation and Verification (ICST), 2020, pp. 402-405, doi: 10.1109/ICST46399.2020.00048. doi: [https://doi.org/10.1109/ICST46399.2020.00048]

## 1. Fichamento de Conteúdo

O artigo se inicia descrevendo como a performance é um fator importante para a qualidade de um _software_ e que com o tempo diversas técnicas de teste de performance foram desenvolvidas para determinar locais que possam diminui-la, tais testes englobam tempo de reposta, taxa de transferência, gasto de recursos e outras métricas. Testes de Performance normalmente executam o _software_ em teste (_software under test (SUT)_) com diversas intensidades de carga e por causa disso demanda uma grande quantidade de tempo e recursos para serem planejados e implementados, com essa informação os autores do artigo apresentam um novo _framework_ para auxiliar a determinar a melhor sequência de testes e a carga de informações otimizada para obtenção das métricas necessárias. A ferramenta funciona seguindo dois dois modelos de _Machine Learning_ realizando os testes de _stress_ usando _SaFReL_(_self-adaptive fuzzy RL-based_) e testes de carga usando uma metodologia baseada em aprendizado reforçado. O _framework_ foi avaliado em relação a sua velocidade, eficiência e adaptabilidade para concluir os objetivos definidos no treinamento e foi possível identificar que ele foi capaz de trabalhar de forma eficiente mesmo com projetos complexos e com grande carga de dados.

## 2. Fichamento Bibliográfico

- _Software under test_: refere-se a um sistema que está sendo testado para operação correta(Pagina 2).
- _SaFReL_ (_self-adaptive fuzzy RL-based_): Metodologia de aprendizado de Machine Learning baseada em Aprendizado por Reforço com o auxilio de lógica Difusa, que inicia as variáveis inicias com valores aleatórios.(Pagina 4)
- Teste de Stress: baseia-se em testar os limites do software e avaliar seu comportamento (Pagina 4).
- Teste de carga: é usado para verificar o limite de dados processados pelo software até que ele não consiga mais processa-lo (Pagina 4).

## 3. Fichamento de Citações

- _"Performance is a software quality characteristic which describes time and resource bound aspects of software behavior. Performance testing is a family of techniques intended to accomplish the objectives of performance evaluation. The objectives are generally considered as measuring performance metrics (e.g. response time, throughput, and resource utilization) and finding performance issues such as specific functional problems emerging under certain execution conditions, e.g. heavy load, and violations of performance requirements."_
- _"Performance modelling and testing techniques are the common approaches to accomplish the objectives of performance evaluation. Model-driven approaches generally involve building a model of the performance behavior of the SUT using the associated modeling notations such as queuing theory, petri nets and Markov processes."_
- _"How we address the challenge. The proposed solution is an autonomous performance testing framework involving two parts: a self-adaptive fuzzy RL-based (SaFReL) stress testing and an RL-driven load testing. Both parts of the framework generally assume two phases of learning: initial and transfer learning. The smart tester agent learns the optimal policy to achieve the intended objective through the initial learning."_
- _"We evaluate the performance of the autonomous framework in terms of effectiveness, efficiency and adaptivity to accomplish the intended objectives, and also examine the behavioral sensitivity of the framework to the learning parameters. We conduct the experimental evaluation of the smart stress testing, SaFReL, on different instances of 12 well-known programs such as Build-apache, n-queens, dcraw, etc. which are characterized with different initial amounts of granted resources and response time requirements."_
- _"The proposed RL-driven performance testing framework is able to accomplish the intended objectives efficiently and adaptively in different testing situations without access to system model or source code."_
