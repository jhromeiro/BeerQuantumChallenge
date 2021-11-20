## BeerQuantumChallenge
# Beer Quantum Challenge Hackathon, Ambev 2021

# Equipe: Qast Quantum Solutions (Arthur Iwakami, Gabriel Valera, João Alves, Yuri Loureiro)


Procuramos aplicar o método de Q-SVM (Quantum Suport Vector Machines) em três contextos diferentes. Dois deles são inspirados da metodologia [deste pre-print](https://arxiv.org/abs/2012.07725) para comparação da Q-SVM e de uma SVM clássica. No último caso, aplicamos  a Q-SVM em uma base de dados artificial que procura replicar dados relativos à manutenção de máquinas, e igualmente comparamos as eficiências do clássico contra o quântico.


- ai4i2020.csv: Base de dados de manutenção utilizada como base para qSVM_maintenance.ipynb. Contém dados classificados simulando medidas de sensores, informações das máquinas e seu estado de funcionamento (falha ou normal).


- nonLinearSep.ipynb: Aplicação do Q-SVM à um conjunto de dados extremamente complexo, onde a eficácia de classificação do algoritmo quântico é esperada ser muito superior à de um algoritmo clásico. 


- xorData.ipynb: Aplicação do Q-SVM à um conjunto de dados mais simples, onde o Q-SVM corre risco de over-fitting se não tomadas as devidas providências. Nos inspiramos das técnicas apresentadas [aqui](https://arxiv.org/abs/2012.07725) para tentar aumentar a eficácia de classificação do Q-SVM.


- qSVM_maintenance.ipynb: Aplicação do Q-SVM à um conjunto de dados mais próximo da realidade da Ambev e da proposta do projeto: manutenção preditiva de equipamento de produção. Utilizamos os dados disponíveis no arquivo ai4i2020.csv .



