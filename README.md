<p align="center">
  <img width="200" height="86" alt="logo_ON" src="https://github.com/user-attachments/assets/7c13bc59-1688-4c84-8662-8656ad4de98c" />
</p>

<h1 align="center"> Estudo dos diferentes perfis da Matéria Escura na Via Láctea </h1>
Representação computacional da distribuição de Matéria Escura (ME) para diferentes perfis teóricos na Via Láctea. O código faz parte do desenvolvimento do projeto de Iniciação Científica "A distribuição de matéria escura e sua conexão com os observáveis", sob orientação da Dra. Clarissa Siqueira, do Observatório Nacional. 

# Índice
* [Introdução](#introdução)
* [Descrição do Projeto](#descrição-do-projeto)
* [Tópicos abordados](#tópicos-abordados)
* [Status do Projeto](#status-do-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Conclusão](#conclusão)

# Introdução
A Matéria Escura (ME) é um dos maiores problemas em aberto na física contemporânea. Apesar de sua existência ser muito bem apoiada por evidências, a busca por entender o que é a ME se complica pela sua baixa interatividade. Assim, um dos primeiros passos a se dar para compreender melhor a natureza dessa matéria é avaliar como ela se distribui em galáxias e aglomerados, uma vez que a ME afeta gravitacionalmente a matéria bariônica. Este projeto utilizou como base o artigo [Cirelli et. al, 2012](https://arxiv.org/abs/1012.4515) (<em>PPPC 4 DM ID - A Poor Particle Physicist Cookbook for Dark Matter Indirect Detection</em>).

# Descrição do projeto 
A partir do artigo Cirelli et. al, foram definidas funções para o cálculo de densidade de Matéria Escura na galáxia para diferentes modelos (perfis): NFW, Einasto, Isothermal, Moore e Burket. Tais densidades foram, então, plotadas em um só gráfico, revelando como esses perfis passam a divergir quando se chega mais próximo do centro galáctico. Isso ocorre por que, devido à grande quantidade de ruído, os dados astrofísicos para essa região são pouco precisos. Assim, o comportamento de cada curva passa a ser ditado por uma interpolação dos próprios perfis, que divergem em algumas características. Logo após essa análise, estudou-se o J-factor da matéria escura e como ele é calculado. Foram feitos outros dois plots: um para o J-factor de decaimentos para os diferentes modelos e outro para o J-factor de aniquilação, ambos em função do ângulo com relação ao centro da galáxia. Por fim, foram realizados plots de J-factors em meshgrids para cada perfil em função das latitude e longitude galácticas, a fim de observar o seu decaimento em função da distância ao CG e sua distribuição esférica.

# Tópicos abordados
- Perfis de densidade de matéria escura
- J-factors de aniquilação e decaimento
- Plot de curvas com Matplotlib
- Integração numérica com Scipy
- Coordenadas galácticas
- Plot de meshgrid

# Status do projeto
O projeto está em andamento. 

# Tecnologias utilizadas
Todo o código foi escrito em Python 3, em um Jupyter Notebook.

# Conclusão
No momento de confecção deste estudo, o projeto de pesquisa ainda se encontrava em seus primeiros momentos. Por esse motivo, o foco foi compreender os primeiros conceitos atrelados à Matéria Escura e como ela se distribui em corpos astrofísicos. A partir disso, a leitura de artigos de apoio e reuniões semanais com a orientadora Dra. Clarissa Siqueira promoveram um aumento do entendimento do aluno quanto a tais tópicos, sendo o presente código a primeira aplicação dessas informações na prática. Sabendo-se da grande importância da computação na Cosmologia e Astrofísica atualmente, desenvolver um código do zero é de extrema importância para o desenvolvimento da iniciação científica em questão. Alguns pontos importantes, como o plot de gráficos de diferentes estilos, o uso de coordenadas astronômicas, a definição de funções e o uso de ferramentas de Python para otimizar o trabalho aprimoraram o conhecimento do estudante em computação, e a visualização de fatos teóricos por meio dos plots demonstrou como a ciência pode ser desenvolvida a partir de observações e teorias, o que é essencial para o prosseguimento do projeto.
