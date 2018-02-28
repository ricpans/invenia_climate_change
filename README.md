# invenia_climate_change

Simulations to curb climate change in a collectivist society

While sitting in a lab, instructions displayed on computers briefed the students in neutral terms regarding the rules of the iterated threshold Public Good Game. The experiments were performed at Yunnan University of Finance and Economics (Kunming, China) with university students still novel to game theory. They took place during 4 different sessions of May and June 2015. The students’ age spanned from 18 to 22 and their geographical provenience varied across different parts of China. A total of 144 students were briefed in neutral terms regarding the rules of the experiment. It consisted of three different treatments looking at intra and intergenerational discounting.
The subjects were free to choose between two behavioural strategies: cooperation and defection. The payoff matrix as designated in the diagram below shows the outcome of the round of each game expressed in earned points. Upper and lower case letters indicate the reading order.

![alt text](https://github.com/ricpans/invenia_climate_change/blob/master/matrix.png)

We acquired two types of empirical data relating to cooperation via z-Tree (Fischbacher 2007). First, we learnt the proportions of cooperation and defection behaviours, and, secondly we discovered the final payoffs gained by each group of 6 students. These sets of data were analysed by Generalized Linear Mixed Models via R 3.2.4 (R_Core_Team 2016) via the lmerTest package (Kuznetsova et al. 2015).

The results we obtained from the Chinese sample show that, differently from the German model whose none of their groups managed to coordinate and invest in group (Jacquet et al. 2013), 5 out of 8 Chinese groups were effective at investing for planting trees.

![alt text](https://github.com/ricpans/invenia_climate_change/blob/master/graph.png)

A Social Value Orientation questionnaire established that collectivistic values allow for the emergence of group cooperation.

![alt text](https://github.com/ricpans/invenia_climate_change/blob/master/pie.png)


Acknowledgements

Hong Liu Li, Xiaoqin Fei, and Chen Shen helped in the organisation of the data collection. RP obtained in 2015 funding from the Chinese Academy of Science President’s International Fellowship Initiative n. 2015PB058, the National Natural Science Foundation of China (NSFC) grant n. 31450110421, and a Microsoft Artificial Intelligence for Earth grant to use A. I. technology to do research about sustainability (58fc59d8-3bdd-40f6-858e-ca39250d6ea9).
References
Fischbacher, U. 2007. z-Tree: Zurich toolbox for ready-made economic experiments. Experimental economics, 10, 171-178
Jacquet, J., Hagel, K., Hauert, C., Marotzke, J., Rohl, T. & Milinski, M. 2013. Intra- and intergenerational discounting in the climate game. Nature Clim. Change, 3, 1025-1028, 10.1038/nclimate2024
http://www.nature.com/nclimate/journal/v3/n12/abs/nclimate2024.html#supplementary-information.
Kuznetsova, A., Brockhoff, P. B. & Christensen, R. H. B. 2015. Package ‘lmerTest’. R package version, 2.0-29
R_Core_Team. 2016. R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. 2015.: R Core Team.
