# BeerQuantumChallenge
## Beer Quantum Challenge Hackathon, Ambev 2021
## Equipe: Qast Quantum Solutions (Arthur Iwakami, Gabriel Valera, João Alves, Yuri Loureiro) - QSVM aplicado à manutenção preditiva de máquinas

Procuramos aplicar o método de Q-SVM (Quantum Suport Vector Machines) em três contextos diferentes afim de comparar a performance do algoritmo quântico em relação à seu equivalente clássico. Dois deles são inspirados da metodologia [deste pre-print](https://arxiv.org/abs/2012.07725) e [este artigo](https://www.nature.com/articles/s41586-019-0980-2) onde conjuntos de dados mais ou menos complexos são utilizados. No último caso, aplicamos a Q-SVM em uma biblioteca de dados artificial que procura replicar dados relativos à manutenção de máquinas, e igualmente comparamos as eficiências do clássico contra o quântico. Encontramos excelente resultados globalmente.

Mais detalhes sobre a implementação, resultados e referências podem ser achados no início de cada notebook Jupyter.

  -  ai4i2020.csv: Base de dados de manutenção utilizada como base para qSVM_maintenance.ipynb. Contém dados classificados simulando medidas de sensores, informações das máquinas e seu estado de funcionamento (falha ou normal).

 -   nonLinearSep.ipynb: Aplicação do Q-SVM à um conjunto de dados extremamente complexo, onde a eficácia de classificação do algoritmo quântico é esperada ser muito superior à de um algoritmo clásico.

 -   xorData.ipynb: Aplicação do Q-SVM à um conjunto de dados mais simples, onde o Q-SVM corre risco de over-fitting se não tomadas as devidas providências. Nos inspiramos das técnicas apresentadas aqui para tentar aumentar a eficácia de classificação do Q-SVM.

 -   qSVM_maintenance.ipynb: Aplicação do Q-SVM à um conjunto de dados mais próximo da realidade da Ambev e da proposta do projeto: manutenção preditiva de equipamento de produção. Utilizamos os dados disponíveis no arquivo ai4i2020.csv .
