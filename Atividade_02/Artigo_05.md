# Towards Automating Code Review Activities

R. Tufano, L. Pascarella, M. Tufano, D. Poshyvanyk and G. Bavota, "Towards Automating Code Review Activities," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 163-174, doi: 10.1109/ICSE43902.2021.00027. doi: [https://doi.org/10.1109/ICSE43902.2021.00027]

## 1. Fichamento de Conteúdo

Um das tarefas que mais gastam tempo do desenvolvedor é a atividade de code review, que apesar de ser extremamente importante para a garantia de um produto de qualidade pode gastar cerca de seis horas semanais, além de aumentar os custos gerais do projeto. A artigo propoe uma maneira de otimizar o processo de _Code Review_ utilizando modelos baseados em _Deep Learning_ para analizar e e indicar parte do codigo nescessarias para serem revisadas. Para realizar o treinamento do modelo apresentado foi criado ferramenta de busca e mineração de repositorios que possuissem a tarefa de _Code Review_ realizada frequentemente, em seguida foi analisada quais eram as sugesoões mais comuns, obtendo mais de 17,194 sugestões de codigo para treinar o modelo.

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
