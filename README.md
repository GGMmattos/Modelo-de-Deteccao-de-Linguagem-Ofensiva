<h1>Construção de modelos de detecção automática de linguagem ofensiva e/ou de ódio em língua portuguesa</h1>

<h3>Resumo</h3>

<p> A web e as redes sociais são espaços de comunicação que permitem a interação, a participação e a mobilização dos usuários, mas também podem ser usados para disseminar conteúdos prejudiciais, como ódio e intolerância. Em vista disso, torna-se necessário buscar formas de combater tal ação de modo a amenizar os danos sociais causados pela propagação desse tipo de conteúdo. Nesse sentido, diversos modelos para a detecção automática de discurso de ódio têm sido propostos pela comunidade científica, inclusive para a língua portuguesa. Tais modelos são treinados por meio de algoritmos de aprendizagem de máquina supervisionados e ajustados para uma base de dados particular. Nesse contexto, o objetivo deste projeto foi avaliar diferentes modelos classificadores de linguagem tóxica e/ou de ódio, visando identificar configurações de aprendizado que se destaquem em termos de desempenho em diferentes bases. Também se verificou a variação de desempenho dos modelos aprendidos quando avaliados em bases de dados diferentes das utilizadas no treinamento. Os resultados mostraram que os modelos BERT superaram os demais e que, dependendo da base de treinamento, há uma queda de desempenho quando o modelo é avaliado com comentários provindos de uma base diferente daquela utilizada para o treinamento. </p>

<h3>Matérias e Métodos </h3>

<p>Foram utilizadas duas bases de dados neste projeto: a ToLD-Br (Toxic Language Dataset for Brazilian Portuguese) (LEITE et al., 2020) e a HateBR (VARGAS et al., 2022). A primeira é composta por comentários coletados da rede social Twitter(X) entre agosto e julho de 2019, sendo 11.745 rotulados como não tóxico (0) e 9.255 como tóxico (1), totalizando 21.000 tweets. A segunda é constituída por comentários retirados da rede social Instagram entre agosto de 2020 e janeiro de 2021, contendo 7.000 comentários, sendo 3.500 não ofensivos (0) e 3.500 ofensivos (1). 
As representações, métodos e algoritmos de AM utilizados neste projeto também se basearam nos trabalhos de Leite et al. (2020) e Vargas et al. (2022), com algumas adaptações nas ferramentas e recursos utilizados. 
Os modelos de classificação foram construídos utilizando a linguagem Python e tal processo pode ser dividido nas etapas descritas a seguir.
</p>
